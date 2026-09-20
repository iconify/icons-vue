<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjtu37bkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="sjtu37bkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:vending-machine-with-heart" /></template>
