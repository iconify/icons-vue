<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gko5i1byl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gko5i1byl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:people-delete-one" /></template>
