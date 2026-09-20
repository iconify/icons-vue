<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzpc1o6iu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="dzpc1o6iu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:recycle-bin-remix" /></template>
