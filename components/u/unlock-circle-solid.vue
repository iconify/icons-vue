<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b90ocibzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="b90ocibzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:unlock-circle-solid" /></template>
