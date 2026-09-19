<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tlxew5wnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":1024};
const content = `<path class="tlxew5wnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:microphonealt" /></template>
