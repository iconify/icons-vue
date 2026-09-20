<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aa6r0qb1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="aa6r0qb1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tidarr-light" /></template>
