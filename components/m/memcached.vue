<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/not9azb9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="not9azb9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:memcached" /></template>
