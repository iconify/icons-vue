<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nwi6y6jmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nwi6y6jmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-half" /></template>
