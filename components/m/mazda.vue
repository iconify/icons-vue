<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kf3aygbvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kf3aygbvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:mazda" /></template>
