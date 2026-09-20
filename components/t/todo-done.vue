<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oh_1n6b9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="oh_1n6b9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:todo-done" /></template>
