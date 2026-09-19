<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/za8njebkw.css';
import '../../css/z/zstbz94ff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<circle class="za8njebkw"/><circle class="zstbz94ff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:record-fill-12" /></template>
