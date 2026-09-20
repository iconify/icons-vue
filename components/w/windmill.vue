<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cahlgsbxb.css';
import '../../css/f/f32tc6mne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cahlgsbxb"/><path class="f32tc6mne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:windmill" /></template>
