<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q1yn3jcfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="q1yn3jcfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:readme" /></template>
