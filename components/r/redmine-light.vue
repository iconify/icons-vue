<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdgn7vb5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mdgn7vb5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:redmine-light" /></template>
