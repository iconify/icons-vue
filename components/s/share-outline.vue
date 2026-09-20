<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bcri59tzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="bcri59tzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:share-outline" /></template>
