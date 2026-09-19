<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a9-n70bna.css';
import '../../css/t/tw2nlk24g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a9-n70bna"/><path class="tw2nlk24g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:message-notification-filled" /></template>
