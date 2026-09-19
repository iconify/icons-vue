<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j9hpkhbur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="j9hpkhbur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:memcached-wordmark" /></template>
