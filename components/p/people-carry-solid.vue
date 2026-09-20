<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjwxeybpm.css';
import '../../css/i/ifjc3lcbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jjwxeybpm"/><path class="ifjc3lcbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:people-carry-solid" /></template>
