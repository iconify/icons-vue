<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m0bq-7bdw.css';
import '../../css/j/jc-qmqbqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m0bq-7bdw"/><path class="jc-qmqbqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:reader-follow-conversation" /></template>
