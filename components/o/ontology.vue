<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ibu_n4bbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ibu_n4bbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:ontology" /></template>
