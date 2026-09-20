<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n77hk2kzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="n77hk2kzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:three-dots-horizontal" /></template>
