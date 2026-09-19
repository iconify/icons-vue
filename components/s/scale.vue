<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/im4sm4brc.css';
import '../../css/v/vyso5givu.css';
import '../../css/f/fb1jcdm6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="im4sm4brc"/><path class="vyso5givu"/><path class="fb1jcdm6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:scale" /></template>
