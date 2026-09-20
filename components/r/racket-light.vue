<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qtb4debnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qtb4debnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:racket-light" /></template>
