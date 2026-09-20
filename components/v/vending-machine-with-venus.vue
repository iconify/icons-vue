<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jp18n-bsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="jp18n-bsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:vending-machine-with-venus" /></template>
