<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-q9d9ndb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x-q9d9ndb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:valve" /></template>
