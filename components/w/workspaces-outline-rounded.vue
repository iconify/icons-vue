<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yp87f3gzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:workspaces-outline-rounded" /></template>
<style>
.yp87f3gzi {
  fill: currentColor;
  d: path("M3.714 19.287q-.945-.945-.945-2.287t.944-2.286T6 13.769t2.286.944T9.232 17t-.944 2.286T6 20.232t-2.286-.945m12 0q-.945-.944-.945-2.286t.944-2.286T18 13.769t2.286.944t.945 2.287t-.945 2.286t-2.286.945t-2.286-.945m-8.138-.71q.655-.655.655-1.576t-.655-1.576T6 14.769t-1.576.655T3.769 17t.655 1.576T6 19.231t1.576-.655m12 0q.655-.655.655-1.576t-.655-1.576T18 14.769t-1.576.655T15.769 17t.655 1.576t1.576.655t1.576-.655m-9.862-9.29Q8.769 8.343 8.769 7t.944-2.286T12 3.769t2.286.945T15.232 7t-.944 2.286t-2.287.945t-2.286-.944m3.862-.711q.655-.655.655-1.576t-.655-1.576T12 4.769t-1.576.655T9.769 7t.655 1.576T12 9.231t1.576-.655M6 17");
}

</style>
