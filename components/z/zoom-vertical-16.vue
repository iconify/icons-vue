<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qsqbu6bax.css';
import '../../css/b/b5tasac6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qsqbu6bax"/><path clip-rule="evenodd" class="b5tasac6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:zoom-vertical-16" /></template>
