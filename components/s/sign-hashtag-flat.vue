<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jbqjqnimp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jbqjqnimp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:sign-hashtag-flat" /></template>
