<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aw5-6um0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aw5-6um0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:pilcrow-solid" /></template>
