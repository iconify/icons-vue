<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g77a37bgg.css';
import '../../css/u/ur3w_zb6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g77a37bgg"/><path class="ur3w_zb6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nicotine-plus-light" /></template>
