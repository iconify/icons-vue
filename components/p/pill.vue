<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jn--jbced.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jn--jbced"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:pill" /></template>
