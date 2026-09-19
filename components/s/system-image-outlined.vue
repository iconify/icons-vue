<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/us2h0wbnz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="us2h0wbnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:system-image-outlined" /></template>
