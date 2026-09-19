<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vi8ojbzph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":896};
const content = `<path class="vi8ojbzph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:mymusic" /></template>
