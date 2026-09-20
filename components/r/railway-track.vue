<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fr8pq4ldz.css';
import '../../css/n/nx5pacs2e.css';
import '../../css/k/k-03aib7l.css';
import '../../css/w/wjfxtcc_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="fr8pq4ldz"/><path class="nx5pacs2e"/><path class="k-03aib7l"/><path class="wjfxtcc_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:railway-track" /></template>
