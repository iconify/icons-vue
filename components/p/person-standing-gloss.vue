<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-l-3bbet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b-l-3bbet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:person-standing-gloss" /></template>
