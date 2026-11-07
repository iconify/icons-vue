<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ex5i2y_lu.css';
import '../../css/k/ka-iktbmz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ex5i2y_lu"/><path class="ka-iktbmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:oven-mitts-minimalistic-bold-duotone" /></template>
