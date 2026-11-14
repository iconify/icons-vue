<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dxvbi8bve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:mode-scene" /></template>
<style>
.dxvbi8bve {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.875 3.25h10.25q2.123 0 3.624 1.501t1.501 3.624v7.25q0 .732-.178 1.39q-.033-.039-.07-.072l-5-4.5q-.053-.048-.114-.085t-.129-.062q-.067-.024-.137-.036t-.142-.01t-.141.017q-.07.016-.135.044q-.066.028-.125.068t-.109.091L14 14.439L9.03 9.47q-.105-.106-.243-.163T8.5 9.25t-.287.057t-.243.163l-6 6q-.088.087-.143.198t-.071.234q-.006-.137-.006-.277v-7.25q0-2.123 1.501-3.624T6.875 3.25M13.5 8.5q0 2.5 2.5 2.5t2.5-2.5T16 6t-2.5 2.5m7.498 9.557q.112.101.253.15q.141.05.29.042q-.322.53-.792 1q-1.501 1.501-3.624 1.501H6.875q-2.123 0-3.624-1.501q-1.29-1.291-1.471-3.041q.053.186.19.322q.105.106.243.163t.287.057t.287-.057t.243-.163l5.47-5.469l4.97 4.969q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094l1.997-1.997z");
}

</style>
