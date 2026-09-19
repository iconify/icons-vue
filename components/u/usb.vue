<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gl6d0daue.css';
import '../../css/h/hnlide_cb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gl6d0daue"/><path class="hnlide_cb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:usb" /></template>
