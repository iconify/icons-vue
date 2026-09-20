<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-cnhtb7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-5,"top":-7};
const content = `<path class="s-cnhtb7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:unordered-list" /></template>
