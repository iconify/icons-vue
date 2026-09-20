<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/brhmcsrhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="brhmcsrhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:notes-book-text" /></template>
