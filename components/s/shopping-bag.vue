<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aags1jb7a.css';
import '../../css/f/fve51_hdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="aags1jb7a"/><path class="fve51_hdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:shopping-bag" /></template>
