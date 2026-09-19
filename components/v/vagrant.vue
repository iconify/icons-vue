<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jmzeugb9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jmzeugb9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:vagrant" /></template>
