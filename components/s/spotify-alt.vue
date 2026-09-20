<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sqjoz67jv.css';
import '../../css/g/gwcmzd5cl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sqjoz67jv"/><path clip-rule="evenodd" class="gwcmzd5cl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:spotify-alt" /></template>
