<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aih13zb3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="aih13zb3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-front-kicking-wearing-martial-arts-belt" /></template>
