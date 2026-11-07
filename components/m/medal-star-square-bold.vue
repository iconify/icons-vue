<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5xllqbwr.css';
import '../../css/z/zzstyjb9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e5xllqbwr"/><path class="zzstyjb9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:medal-star-square-bold" /></template>
