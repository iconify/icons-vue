<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a4zjbgbjz.css';
import '../../css/i/i7fuergcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a4zjbgbjz"/><path class="i7fuergcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:user-clock" /></template>
