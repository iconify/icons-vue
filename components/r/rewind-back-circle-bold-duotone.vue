<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wu-cc3sah.css';
import '../../css/h/htk2wgbva.css';
import '../../css/v/vm55ygbgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wu-cc3sah"/><path class="htk2wgbva"/><path class="vm55ygbgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rewind-back-circle-bold-duotone" /></template>
