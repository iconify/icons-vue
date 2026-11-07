<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6d250bwp.css';
import '../../css/c/cf8jt1bey.css';
import '../../css/j/jt-vrxbga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j6d250bwp"/><path class="cf8jt1bey"/><path clip-rule="evenodd" class="jt-vrxbga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:user-check-rounded-outline" /></template>
