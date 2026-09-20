<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4s1fkb8q.css';
import '../../css/u/ua9aj-d3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v4s1fkb8q"/><path class="ua9aj-d3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:openadserver-dark" /></template>
