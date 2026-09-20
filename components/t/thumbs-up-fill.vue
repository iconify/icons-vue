<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/byuark4es.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="byuark4es"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:thumbs-up-fill" /></template>
