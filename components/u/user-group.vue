<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zjxo99b9u.css';
import '../../css/d/dzyzyeb7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zjxo99b9u"/><path class="dzyzyeb7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:user-group" /></template>
