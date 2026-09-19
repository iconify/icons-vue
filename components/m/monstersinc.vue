<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bzum_2d6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":768};
const content = `<path class="bzum_2d6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:monstersinc" /></template>
