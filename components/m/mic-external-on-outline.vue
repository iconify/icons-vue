<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g3t504yma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mic-external-on-outline" /></template>
<style>
.g3t504yma {
  fill: currentColor;
  d: path("M5.416 7.462q-.26-.33-.396-.714q-.135-.385-.135-.787q0-1.038.73-1.769q.731-.73 1.77-.73q1.038 0 1.769.73t.73 1.77q0 .401-.135.786t-.395.713zm4.776 13.077q-1.361 0-2.334-.973q-.973-.974-.973-2.335h-.77l-.884-8.692h4.308l-.885 8.692h-.77q0 .96.675 1.634q.674.674 1.633.674q.96 0 1.634-.674t.674-1.634V6.769q0-1.361.973-2.335q.973-.973 2.335-.973t2.334.974q.974.973.974 2.334v13.77h-1V6.768q0-.96-.675-1.634q-.674-.674-1.633-.674q-.96 0-1.634.674T13.5 6.77v10.462q0 1.361-.973 2.334t-2.335.973m-3.18-4.307h.746l.657-6.693h-2.06zm.746-6.693H6.354h2.061z");
}

</style>
