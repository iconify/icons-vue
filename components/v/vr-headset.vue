<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kdf5t1bep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kdf5t1bep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:vr-headset" /></template>
