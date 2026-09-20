<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pqm3uvblp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pqm3uvblp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:securityscorecard" /></template>
