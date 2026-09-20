<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0wc3ts_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b0wc3ts_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:song-recommendation-solid" /></template>
