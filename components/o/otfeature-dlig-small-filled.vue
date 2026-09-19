<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ja_yhub6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ja_yhub6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:otfeature-dlig-small-filled" /></template>
