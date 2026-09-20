<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dw--zdb9h.css';
import '../../css/k/k5i8z-b_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dw--zdb9h"/><path class="k5i8z-b_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:map-information-1-filled" /></template>
