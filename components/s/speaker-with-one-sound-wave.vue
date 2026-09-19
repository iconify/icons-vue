<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zwlm6_lai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="zwlm6_lai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:speaker-with-one-sound-wave" /></template>
