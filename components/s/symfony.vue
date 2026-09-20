<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z5rqf2bpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="z5rqf2bpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:symfony" /></template>
