<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ui-2o5b2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ui-2o5b2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:voice-recording-alt" /></template>
