<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vhqdc85vd.css';
import '../../css/c/ceke74b9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vhqdc85vd"/><path class="ceke74b9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:return-up-back-sharp" /></template>
