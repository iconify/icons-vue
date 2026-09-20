<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tw9jp9b-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tw9jp9b-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:share-android-24" /></template>
