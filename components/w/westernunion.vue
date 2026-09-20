<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rf1nmd-il.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rf1nmd-il"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:westernunion" /></template>
