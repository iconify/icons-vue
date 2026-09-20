<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cnddjeb0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cnddjeb0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:user-avatar-light" /></template>
