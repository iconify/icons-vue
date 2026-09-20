<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9uy85bkb.css';
import '../../css/h/hw50cc_wu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x9uy85bkb"/><path class="hw50cc_wu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:mailbox-full-light" /></template>
