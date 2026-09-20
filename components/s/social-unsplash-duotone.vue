<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sp7n27b5q.css';
import '../../css/q/q5eclkb3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sp7n27b5q"/><path clip-rule="evenodd" class="q5eclkb3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:social-unsplash-duotone" /></template>
