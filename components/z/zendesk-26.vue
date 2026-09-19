<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lnrbddcgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="lnrbddcgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:zendesk-26" /></template>
