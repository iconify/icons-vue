<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_2pc4bfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n_2pc4bfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:typeorm" /></template>
