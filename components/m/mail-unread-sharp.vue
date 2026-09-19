<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c4cmerb_j.css';
import '../../css/d/d8hhl9rhn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c4cmerb_j"/><path class="d8hhl9rhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:mail-unread-sharp" /></template>
