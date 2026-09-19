<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dnmne6b8u.css';
import '../../css/b/bsqtkvrgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dnmne6b8u"/><path class="bsqtkvrgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:recently-viewed" /></template>
