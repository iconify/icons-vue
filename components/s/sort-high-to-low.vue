<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hikc9m3jn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="hikc9m3jn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:sort-high-to-low" /></template>
