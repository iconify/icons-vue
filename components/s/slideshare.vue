<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezox_nb2h.css';
import '../../css/s/sigw4fbqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ezox_nb2h"/><path class="sigw4fbqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:slideshare" /></template>
