<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vg-_peskw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="vg-_peskw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:text-document-inverted" /></template>
