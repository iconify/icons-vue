<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whvhgnftn.css';
import '../../css/n/nr45wil8i.css';
import '../../css/x/xi8s70b8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="whvhgnftn"/><path class="nr45wil8i"/><path class="xi8s70b8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:memo" /></template>
