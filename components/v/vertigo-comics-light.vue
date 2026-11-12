<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7m_-rsmc.css';
import '../../css/g/go7xeob4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g7m_-rsmc"/><path class="go7xeob4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:vertigo-comics-light" /></template>
