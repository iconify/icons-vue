<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfxlexb0t.css';
import '../../css/b/bn8wa4tsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="sfxlexb0t"/><path class="bn8wa4tsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:share-fill-12" /></template>
