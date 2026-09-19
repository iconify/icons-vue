<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v2ru2_b2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v2ru2_b2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:share-alt" /></template>
