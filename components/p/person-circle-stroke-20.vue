<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ngyvkq8lm.css';
import '../../css/b/b5it182ov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ngyvkq8lm"/><path class="b5it182ov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:person-circle-stroke-20" /></template>
