<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bydntfeiy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bydntfeiy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:release-notes" /></template>
