<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3h98r3ne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="t3h98r3ne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:otfeature-frac-small-filled" /></template>
