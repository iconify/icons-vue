<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c1croeb4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:nursery-lamp" /></template>
<style>
.c1croeb4x {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.607 4.059q-.067-.091-.157-.159q-2.734-2.05-6.117-1.567T5.9 5.55t-1.567 6.117T7.55 17.1q.439.33.895.594q-.695.555-.695 1.806q0 2.25 2.25 2.25h5q2.25 0 2.25-2.25q0-1.237-.68-1.794q1.45-.816 2.53-2.256q.044-.059.076-.126q.032-.066.051-.138q.018-.071.022-.145t-.007-.147t-.034-.143q-.025-.07-.063-.133q-.037-.064-.087-.119t-.108-.099q-.09-.068-.196-.106q-2.976-1.069-3.423-4.198t2.11-4.989q.121-.088.199-.215q.077-.128.101-.275q.023-.147-.012-.292t-.122-.266");
}

</style>
