<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/urlr-ggas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="urlr-ggas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:share-04" /></template>
