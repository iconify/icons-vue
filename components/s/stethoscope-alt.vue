<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k5j0rp9zi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k5j0rp9zi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:stethoscope-alt" /></template>
