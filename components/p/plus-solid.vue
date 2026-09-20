<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/ww1mpb9-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ww1mpb9-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:plus-solid" /></template>
