<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4uwgeb9s.css';
import '../../css/y/yo4ocac3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="g4uwgeb9s"/><path clip-rule="evenodd" class="yo4ocac3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:youtube-solid" /></template>
