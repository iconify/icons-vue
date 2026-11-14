<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="c2yhqnt3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:work-iq-16-regular" /></template>
<style>
.c2yhqnt3p {
  fill: currentColor;
  d: path("M7.5 9a.5.5 0 0 1 .5.5v5a.5.5 0 0 1-1 0v-5a.5.5 0 0 1 .5-.5M12 9a3 3 0 0 1 2.443 4.736l.41.41a.5.5 0 1 1-.707.707l-.41-.41c-.49.35-1.088.557-1.736.557a3 3 0 0 1 0-6M6.75.639a2.5 2.5 0 0 1 2.5 0l3.247 1.874l.003.002l1.25.721A2.5 2.5 0 0 1 15 5.401V8a.5.5 0 0 1-1 0V5.401a1.5 1.5 0 0 0-.75-1.298l-1.252-.723a1.5 1.5 0 0 0-1.498 0L5.75 6.124A1.5 1.5 0 0 0 5 7.422v4.913c0 .53.285 1.02.746 1.28a.5.5 0 1 1-.492.87l-.066-.04l-.021-.01l-2.912-1.672A2.5 2.5 0 0 1 1 10.595V5.4a2.5 2.5 0 0 1 1.25-2.165zM12 10a2 2 0 1 0 0 4c.37 0 .716-.104 1.014-.28l-.867-.867a.5.5 0 1 1 .707-.707l.867.868A2 2 0 0 0 12 10M8.75 1.505a1.5 1.5 0 0 0-1.5 0l-4.5 2.598A1.5 1.5 0 0 0 2 5.4v5.194a1.5 1.5 0 0 0 .753 1.3l1.265.727A3 3 0 0 1 4 12.335V7.422a2.5 2.5 0 0 1 1.25-2.165L10 2.515a3 3 0 0 1 .269-.134z");
}

</style>
