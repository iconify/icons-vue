<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wz9i_4cdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wz9i_4cdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:user-group-light" /></template>
