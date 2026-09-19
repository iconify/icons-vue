<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yeaa16b2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yeaa16b2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:tooth-braces" /></template>
