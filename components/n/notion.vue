<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zrbkw7bqm.css';
import '../../css/o/oq2mp8bbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zrbkw7bqm"/><path class="oq2mp8bbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:notion" /></template>
