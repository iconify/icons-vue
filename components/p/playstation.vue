<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/monshfqpy.css';
import '../../css/w/wbrphj3qk.css';
import '../../css/s/sc3tshfxe.css';
import '../../css/a/ahxg7rb2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="monshfqpy"/><path class="wbrphj3qk"/><path class="sc3tshfxe"/><path class="ahxg7rb2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:playstation" /></template>
