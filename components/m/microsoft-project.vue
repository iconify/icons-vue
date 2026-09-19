<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a918eqbxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a918eqbxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:microsoft-project" /></template>
