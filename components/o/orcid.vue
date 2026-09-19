<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pw4fyovto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pw4fyovto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:orcid" /></template>
