<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s54wg-5dm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s54wg-5dm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:profile-2user" /></template>
