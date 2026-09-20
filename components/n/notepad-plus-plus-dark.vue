<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-74fqbsy.css';
import '../../css/a/au084ob1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q-74fqbsy"/><path class="au084ob1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:notepad-plus-plus-dark" /></template>
