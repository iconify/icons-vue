<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eqf_9pu9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":768};
const content = `<path class="eqf_9pu9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:pushbullet" /></template>
