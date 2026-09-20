<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dei_17bxy.css';
import '../../css/h/ht7052bix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dei_17bxy"/><path class="ht7052bix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:outbox" /></template>
