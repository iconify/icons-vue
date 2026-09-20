<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxqhc4pom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fxqhc4pom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:zitadel-dark" /></template>
