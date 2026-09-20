<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zuqu0cbld.css';
import '../../css/k/karvylbky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zuqu0cbld"/><path class="karvylbky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:users-fill" /></template>
