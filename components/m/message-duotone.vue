<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/av6p3g-os.css';
import '../../css/h/hdmntob4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="av6p3g-os"/><path class="hdmntob4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:message-duotone" /></template>
