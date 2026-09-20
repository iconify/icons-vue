<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/okxq7jd5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="okxq7jd5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:world" /></template>
