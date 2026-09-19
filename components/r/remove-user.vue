<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ym39ndb8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ym39ndb8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:remove-user" /></template>
