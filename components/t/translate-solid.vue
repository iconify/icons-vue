<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aj_82edkf.css';
import '../../css/b/b6u88sbza.css';
import '../../css/v/vy16ljbzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aj_82edkf"/><path class="b6u88sbza"/><path class="vy16ljbzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:translate-solid" /></template>
