<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b17oeotjk.css';
import '../../css/a/ad5qjploe.css';
import '../../css/l/lvcq9zb7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b17oeotjk"/><path class="ad5qjploe"/><path class="lvcq9zb7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mobilizon" /></template>
