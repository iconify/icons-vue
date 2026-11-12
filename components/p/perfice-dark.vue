<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzt09qmjr.css';
import '../../css/n/ny4v3jcym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zzt09qmjr"/><path class="ny4v3jcym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:perfice-dark" /></template>
