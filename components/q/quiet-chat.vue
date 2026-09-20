<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r60ej9bjx.css';
import '../../css/f/f91k7jbaj.css';
import '../../css/x/xs2wbd9sc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r60ej9bjx"/><path class="f91k7jbaj"/><path class="xs2wbd9sc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:quiet-chat" /></template>
