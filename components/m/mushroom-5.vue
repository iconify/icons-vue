<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/idqiyb76f.css';
import '../../css/h/hwema026b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="idqiyb76f"/><path clip-rule="evenodd" class="hwema026b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:mushroom-5" /></template>
