<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/le5en1tee.css';
import '../../css/e/el2152b6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="le5en1tee"/><path clip-rule="evenodd" class="el2152b6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:trash-16" /></template>
