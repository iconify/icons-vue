<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hmi0dlb7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hmi0dlb7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:pushbullet" /></template>
