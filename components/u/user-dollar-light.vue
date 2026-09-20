<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c46s_0bco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c46s_0bco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:user-dollar-light" /></template>
