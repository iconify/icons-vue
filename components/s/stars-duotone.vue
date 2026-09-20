<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jj-d1dbcu.css';
import '../../css/i/iasza6mmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jj-d1dbcu"/><path class="iasza6mmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:stars-duotone" /></template>
