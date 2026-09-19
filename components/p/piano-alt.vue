<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rv6rrcc7g.css';
import '../../css/b/b7pa4ebgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rv6rrcc7g"/><path class="b7pa4ebgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:piano-alt" /></template>
